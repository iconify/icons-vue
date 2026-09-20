<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etk58nhhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="etk58nhhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:llama-cpp-light" /></template>
