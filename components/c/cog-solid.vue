<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d55gj8bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d55gj8bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cog-solid" /></template>
