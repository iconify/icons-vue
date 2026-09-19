<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf38fyb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="tf38fyb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:comments-dollar" /></template>
