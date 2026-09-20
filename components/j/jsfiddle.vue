<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ned736b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ned736b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:jsfiddle" /></template>
