<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4c4gvlqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u4c4gvlqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:headphones" /></template>
