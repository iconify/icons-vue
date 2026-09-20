<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euw5a4tua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="euw5a4tua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:browser-error-404-remix" /></template>
