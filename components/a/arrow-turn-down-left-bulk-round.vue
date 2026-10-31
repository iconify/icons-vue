<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzcsvybug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzcsvybug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-down-left-bulk-round" /></template>
