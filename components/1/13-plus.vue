<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldx1wpbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldx1wpbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:13-plus" /></template>
