<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6vh3dbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y6vh3dbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:close-filled" /></template>
