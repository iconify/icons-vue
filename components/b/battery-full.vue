<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t737ombpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t737ombpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:battery-full" /></template>
