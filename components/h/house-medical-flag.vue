<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f49xbq6dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="f49xbq6dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-medical-flag" /></template>
