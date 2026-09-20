<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_va5_htj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l_va5_htj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:clean-water-and-sanitation-remix" /></template>
