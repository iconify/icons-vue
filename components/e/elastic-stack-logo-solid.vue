<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7tc2pbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j7tc2pbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elastic-stack-logo-solid" /></template>
