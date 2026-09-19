<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxln1bwak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zxln1bwak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:cursor-click" /></template>
