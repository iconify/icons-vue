<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhda001sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="rhda001sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:globe" /></template>
