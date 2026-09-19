<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwfpi0bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="wwfpi0bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file-audio" /></template>
