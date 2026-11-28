<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lieg9wb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lieg9wb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-open-star" /></template>
