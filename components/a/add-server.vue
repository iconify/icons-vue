<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsryhac7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nsryhac7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:add-server" /></template>
