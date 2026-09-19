<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbt4ulf2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":488};
const content = `<path class="hbt4ulf2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:facebook-places" /></template>
