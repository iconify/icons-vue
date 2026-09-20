<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ric7uy4wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ric7uy4wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hourglass-2-line" /></template>
