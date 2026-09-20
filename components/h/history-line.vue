<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdy-a-bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdy-a-bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:history-line" /></template>
