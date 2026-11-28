<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7o99qb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="y7o99qb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:envelope-x-light" /></template>
