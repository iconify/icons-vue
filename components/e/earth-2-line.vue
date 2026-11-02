<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-4mr4ruq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-4mr4ruq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-2-line" /></template>
