<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd_uy6b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wd_uy6b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:e-wide-with-arrow-bottom-right" /></template>
