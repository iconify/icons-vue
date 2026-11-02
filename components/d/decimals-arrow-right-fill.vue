<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j503dtb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j503dtb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:decimals-arrow-right-fill" /></template>
