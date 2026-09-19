<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epy0a-u5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="epy0a-u5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-chart-bar-20-solid" /></template>
