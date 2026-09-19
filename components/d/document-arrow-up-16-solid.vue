<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duzw7l4-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="duzw7l4-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-arrow-up-16-solid" /></template>
