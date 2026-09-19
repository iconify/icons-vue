<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-c44pbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="h-c44pbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-medical-circle-xmark" /></template>
