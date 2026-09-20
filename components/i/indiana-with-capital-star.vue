<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huc_edb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="huc_edb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:indiana-with-capital-star" /></template>
