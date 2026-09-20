<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa_fyp89y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa_fyp89y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-miniprogram-filled" /></template>
