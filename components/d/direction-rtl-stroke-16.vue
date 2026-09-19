<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocasf0cop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ocasf0cop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:direction-rtl-stroke-16" /></template>
