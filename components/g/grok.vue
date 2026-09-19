<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa-klob7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b qa-klob7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:grok" /></template>
