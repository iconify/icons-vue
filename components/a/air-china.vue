<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi2x4tq6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi2x4tq6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:air-china" /></template>
