<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_e1e9t8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i_e1e9t8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:image-slash-light" /></template>
