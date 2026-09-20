<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5fg72o7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p5fg72o7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-upload-filled" /></template>
