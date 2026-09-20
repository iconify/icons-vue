<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr62-8pji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr62-8pji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-star" /></template>
