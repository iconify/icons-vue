<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axf4zelnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="axf4zelnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:interface-definition" /></template>
