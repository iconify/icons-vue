<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhkdtwb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jhkdtwb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:hand" /></template>
