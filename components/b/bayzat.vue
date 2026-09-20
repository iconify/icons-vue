<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8c01bogj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":23};
const content = `<path class="v8c01bogj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bayzat" /></template>
