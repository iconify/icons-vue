<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl1ddvjxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="yl1ddvjxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:id-card-clip" /></template>
