<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp4xoebgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tp4xoebgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-bin" /></template>
