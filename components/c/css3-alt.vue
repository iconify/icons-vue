<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7f12mbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="g7f12mbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:css3-alt" /></template>
