<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfd4fdc5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="wfd4fdc5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-pointer" /></template>
