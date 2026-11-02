<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fndko-17y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fndko-17y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-in-control-point-line" /></template>
