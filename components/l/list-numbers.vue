<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvpejw8_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nvpejw8_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:list-numbers" /></template>
