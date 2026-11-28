<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy9r2vnub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy9r2vnub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-commit-solid" /></template>
