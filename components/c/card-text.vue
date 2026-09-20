<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6skqbbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="w6skqbbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:card-text" /></template>
