<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvykp38uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mvykp38uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cart-arrow-down" /></template>
