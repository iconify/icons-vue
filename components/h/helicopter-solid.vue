<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtksn9bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qtksn9bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:helicopter-solid" /></template>
