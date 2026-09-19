<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap5cqxbrg.css';
import '../../css/w/wzyv4j1bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ap5cqxbrg"/><path class="wzyv4j1bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:add-filled" /></template>
