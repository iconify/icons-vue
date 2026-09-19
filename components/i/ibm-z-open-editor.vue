<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxo54sbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zxo54sbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-z-open-editor" /></template>
