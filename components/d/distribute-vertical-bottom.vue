<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9bpb7vag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l9bpb7vag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:distribute-vertical-bottom" /></template>
