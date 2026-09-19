<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixx4r3bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixx4r3bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-model-context-protocol" /></template>
