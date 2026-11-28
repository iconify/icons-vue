<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q33dsdzhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q33dsdzhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-slash-light" /></template>
