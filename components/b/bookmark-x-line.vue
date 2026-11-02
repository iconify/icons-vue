<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1yfpabfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1yfpabfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-x-line" /></template>
