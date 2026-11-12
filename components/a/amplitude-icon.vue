<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yps82ibbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":800};
const content = `<path class="yps82ibbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amplitude-icon" /></template>
