<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmb3o0bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="cmb3o0bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cloud-showers-water" /></template>
