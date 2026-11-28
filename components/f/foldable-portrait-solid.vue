<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzyapqb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzyapqb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:foldable-portrait-solid" /></template>
