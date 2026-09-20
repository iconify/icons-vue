<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn5it8i0p.css';
import '../../css/a/az2bjjb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn5it8i0p"/><path class="az2bjjb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dotenvx" /></template>
