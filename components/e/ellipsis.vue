<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zymh_bb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zymh_bb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ellipsis" /></template>
