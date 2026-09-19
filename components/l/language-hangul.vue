<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk2198b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vk2198b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-hangul" /></template>
