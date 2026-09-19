<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r595-ubef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="r595-ubef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:business-time" /></template>
