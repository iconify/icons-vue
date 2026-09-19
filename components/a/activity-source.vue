<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8--ehbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s8--ehbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:activity-source" /></template>
