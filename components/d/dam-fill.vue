<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9p5-ofhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9p5-ofhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dam-fill" /></template>
