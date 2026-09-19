<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iotkxsz-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="iotkxsz-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-left-circle-20-solid" /></template>
