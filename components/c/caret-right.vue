<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tytlidciu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tytlidciu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:caret-right" /></template>
