<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktmk6lb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ktmk6lb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:font-awesome" /></template>
