<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_5ziluza.css';
import '../../css/x/xi4gy0bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_5ziluza"/><path class="xi4gy0bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:homepod-line" /></template>
