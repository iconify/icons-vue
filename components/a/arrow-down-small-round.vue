<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muf-8jbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muf-8jbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-small-round" /></template>
