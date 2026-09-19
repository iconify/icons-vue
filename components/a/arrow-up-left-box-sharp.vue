<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grqjw4bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="grqjw4bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-left-box-sharp" /></template>
