<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w65ko2ctp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w65ko2ctp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:braces-solid" /></template>
