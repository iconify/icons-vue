<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8lfz7jtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8lfz7jtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-3-line" /></template>
