<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b17ogtb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b17ogtb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eight-track" /></template>
