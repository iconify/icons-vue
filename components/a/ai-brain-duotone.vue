<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr1jelbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr1jelbwk primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-brain-duotone" /></template>
