<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfhdwq6la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pfhdwq6la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:beancount" /></template>
