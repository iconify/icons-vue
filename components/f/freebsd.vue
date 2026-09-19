<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ine3pyb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ine3pyb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:freebsd" /></template>
