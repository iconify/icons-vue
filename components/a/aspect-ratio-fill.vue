<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld8o_abgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld8o_abgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aspect-ratio-fill" /></template>
