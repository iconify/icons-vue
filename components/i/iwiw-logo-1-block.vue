<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al6eot8sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="al6eot8sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:iwiw-logo-1-block" /></template>
