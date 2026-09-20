<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s413akbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s413akbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:arrow-left" /></template>
