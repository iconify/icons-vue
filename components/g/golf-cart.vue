<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3bltac4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t3bltac4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:golf-cart" /></template>
