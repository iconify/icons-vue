<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdl7-9bot.css';
import '../../css/x/xyt0ejbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qdl7-9bot"/><path class="xyt0ejbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-charging-20" /></template>
