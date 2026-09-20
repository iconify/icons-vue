<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuilpbbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuilpbbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-upload-fill" /></template>
