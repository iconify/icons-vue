<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj53xpbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="bj53xpbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cart-flatbed" /></template>
