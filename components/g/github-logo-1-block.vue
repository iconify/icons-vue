<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr-3rds0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dr-3rds0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:github-logo-1-block" /></template>
