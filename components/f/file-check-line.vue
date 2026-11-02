<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_4_h7yce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_4_h7yce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-check-line" /></template>
