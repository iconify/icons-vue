<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/samnvgb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="samnvgb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:bag" /></template>
