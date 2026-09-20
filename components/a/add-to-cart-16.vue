<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycjak9csk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ycjak9csk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:add-to-cart-16" /></template>
