<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j01aanbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j01aanbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bar-assistant-dark" /></template>
