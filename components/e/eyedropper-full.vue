<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq79_r4_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sq79_r4_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:eyedropper-full" /></template>
