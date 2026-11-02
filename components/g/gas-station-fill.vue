<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw4gn5mis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw4gn5mis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gas-station-fill" /></template>
