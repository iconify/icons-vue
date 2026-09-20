<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvftmg39e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cvftmg39e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:file" /></template>
