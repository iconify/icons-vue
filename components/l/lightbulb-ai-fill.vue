<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr1zckasm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr1zckasm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lightbulb-ai-fill" /></template>
