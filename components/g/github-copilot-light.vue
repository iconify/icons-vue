<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxv435yty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sxv435yty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:github-copilot-light" /></template>
