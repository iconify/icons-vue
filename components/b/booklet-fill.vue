<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr076mb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr076mb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:booklet-fill" /></template>
