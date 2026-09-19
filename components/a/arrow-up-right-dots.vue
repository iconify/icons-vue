<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_8yhzb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="c_8yhzb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-up-right-dots" /></template>
