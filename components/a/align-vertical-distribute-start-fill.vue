<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc6ulacjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc6ulacjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-vertical-distribute-start-fill" /></template>
