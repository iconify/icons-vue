<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xae4x2bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xae4x2bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forklift-fill" /></template>
