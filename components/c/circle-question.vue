<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqyr3mqxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hqyr3mqxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-question" /></template>
