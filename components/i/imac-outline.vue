<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdtr9bfpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hdtr9bfpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:imac-outline" /></template>
