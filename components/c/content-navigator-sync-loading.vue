<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxtxmq4qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rxtxmq4qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:content-navigator-sync-loading" /></template>
