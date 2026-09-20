<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz4v40_rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hz4v40_rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bag-pound-remix" /></template>
