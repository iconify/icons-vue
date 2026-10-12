<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv8c1bcfz.css';
import '../../css/w/wvb1r7csl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv8c1bcfz"/><path clip-rule="evenodd" class="wvb1r7csl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:crop-filled" /></template>
