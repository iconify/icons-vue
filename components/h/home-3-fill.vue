<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5ljbpb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ljbpb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-3-fill" /></template>
