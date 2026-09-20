<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpp468b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hpp468b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:banana" /></template>
