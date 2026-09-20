<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyr2ydbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xyr2ydbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:block-1-flat" /></template>
