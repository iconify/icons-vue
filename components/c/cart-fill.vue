<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nggkwabds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nggkwabds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cart-fill" /></template>
