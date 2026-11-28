<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_7r6jbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_7r6jbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-sparkles-solid" /></template>
