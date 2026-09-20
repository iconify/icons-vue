<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff6qa3bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ff6qa3bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hospital" /></template>
