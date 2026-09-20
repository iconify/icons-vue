<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndub7cbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndub7cbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:codeigniter-logo-solid" /></template>
