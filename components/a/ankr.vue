<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb5_0-b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xb5_0-b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ankr" /></template>
