<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqhbtbcua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nqhbtbcua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-php-bold" /></template>
