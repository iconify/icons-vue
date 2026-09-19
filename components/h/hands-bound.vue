<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9v5rqj_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="c9v5rqj_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hands-bound" /></template>
