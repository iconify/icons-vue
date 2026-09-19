<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx9dqebgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kx9dqebgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:abap" /></template>
