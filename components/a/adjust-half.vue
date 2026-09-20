<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-_j0scof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-_j0scof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:adjust-half" /></template>
