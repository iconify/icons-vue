<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzw45xbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wzw45xbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-alexa" /></template>
