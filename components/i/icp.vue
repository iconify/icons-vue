<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4xo2jmoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v4xo2jmoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:icp" /></template>
