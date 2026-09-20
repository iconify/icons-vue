<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd2gdm8fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd2gdm8fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:indeterminate-check-box" /></template>
