<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stetxqbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stetxqbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-text-round" /></template>
