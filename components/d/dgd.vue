<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4pxzd2th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n4pxzd2th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dgd" /></template>
