<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwe37rb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwe37rb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:goblet-2-line" /></template>
