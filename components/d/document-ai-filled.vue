<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucsmcqbrq.css';
import '../../css/f/f1ouj-bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucsmcqbrq"/><path class="f1ouj-bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-ai-filled" /></template>
