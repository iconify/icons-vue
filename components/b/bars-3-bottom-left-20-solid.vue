<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3j-ezfuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m3j-ezfuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-bottom-left-20-solid" /></template>
