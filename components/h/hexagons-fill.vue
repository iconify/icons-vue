<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llibqiifx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="llibqiifx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hexagons-fill" /></template>
