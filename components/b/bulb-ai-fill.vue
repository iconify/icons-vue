<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpw4mub2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpw4mub2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-ai-fill" /></template>
