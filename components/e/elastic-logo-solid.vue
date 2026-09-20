<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3qec3ejp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3qec3ejp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elastic-logo-solid" /></template>
