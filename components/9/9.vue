<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsf0zp73a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="nsf0zp73a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:9" /></template>
