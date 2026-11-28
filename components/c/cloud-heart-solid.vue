<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsu8t_9kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsu8t_9kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-heart-solid" /></template>
