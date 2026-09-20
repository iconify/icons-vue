<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl7ioxuie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hl7ioxuie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:inkscape-logo-block" /></template>
