<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qniucrb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qniucrb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-bottom-bold" /></template>
