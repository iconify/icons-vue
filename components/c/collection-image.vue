<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7381obji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="e7381obji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-image" /></template>
