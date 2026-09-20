<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpalc1bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpalc1bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-edit-line" /></template>
