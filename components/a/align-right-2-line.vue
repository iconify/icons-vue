<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srzp5ibqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srzp5ibqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-right-2-line" /></template>
