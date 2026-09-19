<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjtmj6bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rjtmj6bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:caret-square-up" /></template>
