<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6c7ln5ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":560,"height":850};
const content = `<path class="f6c7ln5ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:file" /></template>
