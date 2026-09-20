<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7mof65cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7mof65cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ltc" /></template>
