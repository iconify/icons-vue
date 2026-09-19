<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmk5e-bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xmk5e-bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:filter" /></template>
