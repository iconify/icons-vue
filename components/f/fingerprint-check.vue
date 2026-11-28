<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfa9x7v7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfa9x7v7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fingerprint-check" /></template>
