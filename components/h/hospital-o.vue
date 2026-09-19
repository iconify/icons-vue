<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aidoxu2xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1792};
const content = `<path class="aidoxu2xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hospital-o" /></template>
