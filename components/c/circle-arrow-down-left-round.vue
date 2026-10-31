<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xayu7zctl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xayu7zctl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-down-left-round" /></template>
