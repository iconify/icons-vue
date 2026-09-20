<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi6y_vvsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi6y_vvsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-settings-line" /></template>
