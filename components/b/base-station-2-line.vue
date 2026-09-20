<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj4m-lvhg.css';
import '../../css/a/a0xu55but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj4m-lvhg"/><path class="a0xu55but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:base-station-2-line" /></template>
