<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icwdcg1df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1664};
const content = `<path class="icwdcg1df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:camera" /></template>
