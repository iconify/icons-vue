<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyo59fb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyo59fb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-circle-line" /></template>
