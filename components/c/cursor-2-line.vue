<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtrip9bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtrip9bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-2-line" /></template>
