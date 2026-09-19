<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6mqhy2_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e6mqhy2_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-infinite" /></template>
