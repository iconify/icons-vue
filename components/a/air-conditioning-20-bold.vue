<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb32smlnz.css';
import '../../css/t/tznykc51m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vb32smlnz"/><path class="tznykc51m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-conditioning-20-bold" /></template>
