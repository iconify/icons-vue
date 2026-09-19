<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp255lbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pp255lbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:currency-euro" /></template>
