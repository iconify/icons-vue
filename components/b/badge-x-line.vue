<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv55x9vmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv55x9vmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-x-line" /></template>
