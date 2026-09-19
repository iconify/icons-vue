<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xey49acws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xey49acws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-paragraph" /></template>
