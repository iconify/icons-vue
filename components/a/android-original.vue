<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpm6hqb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hpm6hqb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:android-original" /></template>
