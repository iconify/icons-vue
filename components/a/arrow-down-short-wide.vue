<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjp21nb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="cjp21nb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-down-short-wide" /></template>
