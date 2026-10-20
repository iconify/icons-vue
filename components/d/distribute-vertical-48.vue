<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiuavghpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xiuavghpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:distribute-vertical-48" /></template>
