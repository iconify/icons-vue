<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te2lyebrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="te2lyebrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:folder-arrow-up-bold" /></template>
