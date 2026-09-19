<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8h25poui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t8h25poui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:heart-circle-minus" /></template>
