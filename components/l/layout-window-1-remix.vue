<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg6ks6bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pg6ks6bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layout-window-1-remix" /></template>
