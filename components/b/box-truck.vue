<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8ooa6h5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v8ooa6h5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:box-truck" /></template>
