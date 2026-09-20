<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr23eyx7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xr23eyx7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:layers" /></template>
