<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sknjbp8wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sknjbp8wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:centos" /></template>
