<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz1upf8ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz1upf8ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hand-coin" /></template>
