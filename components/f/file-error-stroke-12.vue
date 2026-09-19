<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yasyzz4_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yasyzz4_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-error-stroke-12" /></template>
