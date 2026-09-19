<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6_iq1b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="c6_iq1b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cart-arrow-down" /></template>
