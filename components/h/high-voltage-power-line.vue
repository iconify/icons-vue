<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-j5vklnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-j5vklnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:high-voltage-power-line" /></template>
