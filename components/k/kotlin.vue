<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylz3-15ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ylz3-15ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:kotlin" /></template>
