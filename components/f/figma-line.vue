<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo775lb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo775lb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:figma-line" /></template>
