<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb7n7cbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb7n7cbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-code-solid" /></template>
