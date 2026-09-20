<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niohfvb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="niohfvb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:embassy-10" /></template>
