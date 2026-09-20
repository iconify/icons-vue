<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbsoh586u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kbsoh586u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:laptop" /></template>
