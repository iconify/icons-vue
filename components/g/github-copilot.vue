<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbj_t9bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kbj_t9bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:github-copilot" /></template>
