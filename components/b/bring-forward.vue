<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v15db6dui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v15db6dui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bring-forward" /></template>
