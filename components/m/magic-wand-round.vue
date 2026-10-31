<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eotd31bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eotd31bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:magic-wand-round" /></template>
