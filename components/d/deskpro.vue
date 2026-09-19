<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztsv9wbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="ztsv9wbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:deskpro" /></template>
