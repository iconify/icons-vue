<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-xf0nvoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o-xf0nvoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:battery-three-quarters-solid" /></template>
