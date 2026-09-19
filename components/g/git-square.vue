<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vou3_l7ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vou3_l7ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:git-square" /></template>
