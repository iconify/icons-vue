<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whpbu3b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="whpbu3b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:convert-to-cloud" /></template>
