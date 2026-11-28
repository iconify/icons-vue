<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc6qaeban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tc6qaeban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-left-fill" /></template>
