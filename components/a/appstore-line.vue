<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr1y-fbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr1y-fbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:appstore-line" /></template>
