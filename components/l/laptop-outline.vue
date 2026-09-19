<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxciqpbda.css';
import '../../css/f/fne6a9bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="zxciqpbda"/><path class="fne6a9bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:laptop-outline" /></template>
