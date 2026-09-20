<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akz0ez_3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="akz0ez_3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:heart-off" /></template>
