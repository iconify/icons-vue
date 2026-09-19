<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqwj2_7hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="hqwj2_7hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:apple-whole" /></template>
