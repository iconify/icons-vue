<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymx794b5s.css';
import '../../css/h/h1_3onb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymx794b5s"/><path class="h1_3onb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-setting-filled" /></template>
