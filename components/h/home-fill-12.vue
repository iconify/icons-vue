<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f53z1qbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f53z1qbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:home-fill-12" /></template>
