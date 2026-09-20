<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l92x6sbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l92x6sbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-3-line" /></template>
