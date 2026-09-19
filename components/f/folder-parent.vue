<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt4rfofpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bt4rfofpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder-parent" /></template>
