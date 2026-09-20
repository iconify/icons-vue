<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb-ylj57l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb-ylj57l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-circles-sharp-fill" /></template>
