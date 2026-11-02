<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ettsd2jzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ettsd2jzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-signal-line" /></template>
