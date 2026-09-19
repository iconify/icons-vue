<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abb0r1czz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="abb0r1czz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-crack" /></template>
