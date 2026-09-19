<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybb-y_bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ybb-y_bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-turn-up-left" /></template>
