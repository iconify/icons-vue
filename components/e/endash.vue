<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0bly_bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":336,"height":614};
const content = `<path class="d0bly_bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:endash" /></template>
