<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr6ny4mjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sr6ny4mjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lowered-curb-with-arrow-bottom-right" /></template>
