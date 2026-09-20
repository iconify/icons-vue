<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eugv6vbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eugv6vbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:caret-square-left-solid" /></template>
