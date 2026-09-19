<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mweid1b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mweid1b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:grabber" /></template>
