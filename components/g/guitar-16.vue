<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojsua1phm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ojsua1phm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-16" /></template>
