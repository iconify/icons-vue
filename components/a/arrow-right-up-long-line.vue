<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1x5hz-hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1x5hz-hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-up-long-line" /></template>
