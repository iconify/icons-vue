<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v71i76b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v71i76b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:image-plus-bold" /></template>
