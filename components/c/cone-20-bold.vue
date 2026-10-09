<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6azyy2ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6azyy2ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cone-20-bold" /></template>
