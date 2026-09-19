<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptjs_9bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="ptjs_9bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:creative-commons-sampling" /></template>
