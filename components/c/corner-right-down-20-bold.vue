<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tex_f1bsd.css';
import '../../css/q/q4u-icn5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tex_f1bsd"/><path class="q4u-icn5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-right-down-20-bold" /></template>
