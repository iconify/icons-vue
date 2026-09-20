<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knt06ccrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="knt06ccrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dashboard-3-solid" /></template>
