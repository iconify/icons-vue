<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xop6-hfiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xop6-hfiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-x-line" /></template>
