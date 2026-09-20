<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7p5hdbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m7p5hdbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:checklist-minimalistic-bold" /></template>
