<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrum8s9ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rrum8s9ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-up-20-solid" /></template>
