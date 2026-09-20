<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qie5wsm-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qie5wsm-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:heading-1-paragraph-styles-heading" /></template>
