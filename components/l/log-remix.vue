<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us5-5pbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="us5-5pbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:log-remix" /></template>
