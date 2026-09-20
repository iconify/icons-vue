<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmcxs6-ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rmcxs6-ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:compass-north-west" /></template>
