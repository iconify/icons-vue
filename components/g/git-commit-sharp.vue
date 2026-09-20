<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_f-9jb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_f-9jb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:git-commit-sharp" /></template>
