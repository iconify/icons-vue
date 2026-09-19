<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0ole3zzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f0ole3zzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:array-strings" /></template>
