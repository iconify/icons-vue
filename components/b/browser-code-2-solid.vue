<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w39cyh2fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w39cyh2fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:browser-code-2-solid" /></template>
