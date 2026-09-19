<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tllzkn6fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tllzkn6fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dice-1-fill" /></template>
