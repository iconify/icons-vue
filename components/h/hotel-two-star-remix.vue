<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my9zteq1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="my9zteq1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hotel-two-star-remix" /></template>
