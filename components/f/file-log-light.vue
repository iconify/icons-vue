<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyxh0zbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oyxh0zbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-log-light" /></template>
