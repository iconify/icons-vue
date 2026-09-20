<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffr4accln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffr4accln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:link-share-2-solid" /></template>
