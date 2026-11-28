<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfamr8bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfamr8bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:fingerprint" /></template>
