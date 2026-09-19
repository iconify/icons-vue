<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo0c_kb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="mo0c_kb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:circle-solid" /></template>
