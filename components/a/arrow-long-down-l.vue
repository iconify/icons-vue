<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iihu-ug8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iihu-ug8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-down-l" /></template>
