<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/int_qkbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="int_qkbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:3d-model" /></template>
