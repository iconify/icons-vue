<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t25i1-lkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t25i1-lkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-check-16-solid" /></template>
