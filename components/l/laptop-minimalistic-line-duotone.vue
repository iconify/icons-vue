<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hgy-6rbgh.css';
import '../../css/d/dr6ywvblz.css';
import '../../css/y/y94j8l0lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hgy-6rbgh"/><path class="dr6ywvblz"/><path class="y94j8l0lc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-minimalistic-line-duotone" /></template>
