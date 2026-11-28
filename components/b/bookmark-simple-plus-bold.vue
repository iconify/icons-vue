<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg4oj7sun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="eg4oj7sun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-plus-bold" /></template>
