<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlq7aeugm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlq7aeugm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:corner-up-left" /></template>
