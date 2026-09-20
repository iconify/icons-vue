<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yimt7bc-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yimt7bc-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:colorado-with-capital-star" /></template>
