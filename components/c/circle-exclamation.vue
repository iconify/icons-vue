<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zigurz_7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zigurz_7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-exclamation" /></template>
