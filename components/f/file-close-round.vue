<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe509mbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe509mbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-close-round" /></template>
