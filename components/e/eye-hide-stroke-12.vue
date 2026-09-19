<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjr8m78kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sjr8m78kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eye-hide-stroke-12" /></template>
