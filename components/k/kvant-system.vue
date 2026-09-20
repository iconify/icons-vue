<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwxwddxbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":171};
const content = `<path class="kwxwddxbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kvant-system" /></template>
