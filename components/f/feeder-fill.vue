<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksa1a5y2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksa1a5y2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:feeder-fill" /></template>
