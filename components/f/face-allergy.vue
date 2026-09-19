<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xorx1caxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="xorx1caxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:face-allergy" /></template>
