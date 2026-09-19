<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uug-36bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="uug-36bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:figma" /></template>
