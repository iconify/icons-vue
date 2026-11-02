<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krrk9_xhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krrk9_xhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-1-fill" /></template>
