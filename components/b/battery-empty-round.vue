<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5cftmb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5cftmb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-empty-round" /></template>
