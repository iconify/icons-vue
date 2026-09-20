<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uosz9fbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uosz9fbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hierarchy-1-solid" /></template>
