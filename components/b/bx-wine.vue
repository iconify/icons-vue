<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie19m8b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie19m8b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-wine" /></template>
