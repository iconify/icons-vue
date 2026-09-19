<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyu5r4bdv.css';
import '../../css/g/gwp8_q19n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyu5r4bdv"/><path class="gwp8_q19n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock" /></template>
