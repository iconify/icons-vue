<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bav46-0mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bav46-0mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:linux" /></template>
