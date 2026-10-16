<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq7ovqb7o.css';
import '../../css/i/iace3isjh.css';
import '../../css/k/kokl_z4xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oq7ovqb7o"/><path class="iace3isjh"/><path class="kokl_z4xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-trailer-20-bold" /></template>
