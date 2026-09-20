<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3a7ce9nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d3a7ce9nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:link-chain-solid" /></template>
