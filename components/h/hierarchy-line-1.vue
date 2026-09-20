<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epwuo5bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epwuo5bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:hierarchy-line-1" /></template>
