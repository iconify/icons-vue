<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksirtqb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ksirtqb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:information-circle-solid" /></template>
