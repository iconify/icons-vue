<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-t15ibmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="d-t15ibmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-bottom-left-circle" /></template>
