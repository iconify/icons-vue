<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdwuscnah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cdwuscnah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:command-line" /></template>
