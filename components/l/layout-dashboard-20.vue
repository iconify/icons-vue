<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9xc3xfxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f9xc3xfxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layout-dashboard-20" /></template>
