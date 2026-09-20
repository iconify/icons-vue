<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd85a1byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wd85a1byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:blackberry" /></template>
