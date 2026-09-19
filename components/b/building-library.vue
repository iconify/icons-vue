<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpgr4xl-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qpgr4xl-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:building-library" /></template>
