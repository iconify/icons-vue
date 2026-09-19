<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neuquygwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1408};
const content = `<path class="neuquygwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cart-plus" /></template>
