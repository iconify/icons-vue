<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8dsq4bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n8dsq4bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:faceplate-container" /></template>
