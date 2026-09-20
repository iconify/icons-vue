<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbu9pnvty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbu9pnvty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-circle-off-line" /></template>
