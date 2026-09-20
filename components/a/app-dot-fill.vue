<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpg27mbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpg27mbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-dot-fill" /></template>
