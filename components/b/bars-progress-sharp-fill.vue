<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez-140r2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez-140r2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bars-progress-sharp-fill" /></template>
