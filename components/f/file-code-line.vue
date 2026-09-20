<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_r2nqbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_r2nqbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-code-line" /></template>
