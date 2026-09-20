<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjl-qiiho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjl-qiiho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:basecamp-logo-2" /></template>
