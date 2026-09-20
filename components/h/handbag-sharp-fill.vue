<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq-vnebps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fq-vnebps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:handbag-sharp-fill" /></template>
