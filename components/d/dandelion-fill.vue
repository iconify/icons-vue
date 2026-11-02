<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iywoivxjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iywoivxjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dandelion-fill" /></template>
