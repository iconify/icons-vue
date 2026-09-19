<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yprv9ybsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yprv9ybsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cabin-care-alt" /></template>
