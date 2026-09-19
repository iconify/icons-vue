<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7dqhqbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e7dqhqbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cloud-download-outline" /></template>
