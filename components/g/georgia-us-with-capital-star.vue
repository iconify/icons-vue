<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziy4my_3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ziy4my_3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:georgia-us-with-capital-star" /></template>
