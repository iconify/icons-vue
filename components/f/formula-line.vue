<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb2p2fu8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb2p2fu8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:formula-line" /></template>
