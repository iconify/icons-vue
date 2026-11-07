<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk_r9ibjr.css';
import '../../css/v/vj58-bbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jk_r9ibjr"/><path class="vj58-bbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-upload-outline" /></template>
