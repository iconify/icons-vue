<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8jdxt_7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="x8jdxt_7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:closed-captioning" /></template>
