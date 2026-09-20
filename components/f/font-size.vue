<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdir__byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdir__byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:font-size" /></template>
