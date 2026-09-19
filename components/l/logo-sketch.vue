<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drqt8gmkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="drqt8gmkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-sketch" /></template>
