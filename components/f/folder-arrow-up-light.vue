<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6l52tzsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x6l52tzsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:folder-arrow-up-light" /></template>
