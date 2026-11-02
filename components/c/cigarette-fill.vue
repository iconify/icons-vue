<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwzk0jram.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwzk0jram"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cigarette-fill" /></template>
