<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmar9isaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qmar9isaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:consume-outline" /></template>
