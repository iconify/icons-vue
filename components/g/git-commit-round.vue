<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knui3cfem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knui3cfem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-commit-round" /></template>
