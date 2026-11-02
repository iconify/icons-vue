<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bppp0b1tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bppp0b1tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-7-fill" /></template>
