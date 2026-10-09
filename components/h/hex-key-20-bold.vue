<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmrel0uvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dmrel0uvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hex-key-20-bold" /></template>
