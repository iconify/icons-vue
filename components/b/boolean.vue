<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kff4x-c4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kff4x-c4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:boolean" /></template>
