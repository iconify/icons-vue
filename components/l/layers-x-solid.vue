<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq0b9pwmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq0b9pwmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-x-solid" /></template>
