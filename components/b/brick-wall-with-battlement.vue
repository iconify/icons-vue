<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0j8rpbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m0j8rpbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:brick-wall-with-battlement" /></template>
