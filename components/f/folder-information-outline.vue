<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrzf860or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrzf860or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-information-outline" /></template>
