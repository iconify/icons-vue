<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6wyyfavg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6wyyfavg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ghost-3-line" /></template>
