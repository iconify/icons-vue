<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpe1u1b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wpe1u1b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-right-bold" /></template>
