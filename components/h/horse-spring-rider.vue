<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-ol71utl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t-ol71utl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horse-spring-rider" /></template>
