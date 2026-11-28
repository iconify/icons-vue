<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf61v62zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wf61v62zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:headphones-slash-light" /></template>
