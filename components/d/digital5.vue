<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3sbu1bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q3sbu1bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital5" /></template>
