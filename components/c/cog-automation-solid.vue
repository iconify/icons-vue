<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf-n46rwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nf-n46rwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cog-automation-solid" /></template>
