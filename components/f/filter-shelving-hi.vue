<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkgi4lmks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jkgi4lmks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:filter-shelving-hi" /></template>
