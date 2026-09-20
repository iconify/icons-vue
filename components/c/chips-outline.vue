<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr2gxdbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qr2gxdbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:chips-outline" /></template>
