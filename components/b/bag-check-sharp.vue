<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnge6pbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wnge6pbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bag-check-sharp" /></template>
