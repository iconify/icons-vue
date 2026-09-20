<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd1r2ibat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kd1r2ibat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hotel-shower-head" /></template>
