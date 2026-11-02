<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkhbm6bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkhbm6bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-up-line" /></template>
