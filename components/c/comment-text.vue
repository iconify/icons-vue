<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7kopvl8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7kopvl8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:comment-text" /></template>
