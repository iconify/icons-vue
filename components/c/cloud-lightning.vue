<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me23wzbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="me23wzbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-lightning" /></template>
