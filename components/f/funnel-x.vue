<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqqft4rjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqqft4rjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:funnel-x" /></template>
