<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhgdo6bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hhgdo6bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dam" /></template>
