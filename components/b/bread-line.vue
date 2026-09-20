<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etvdebbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etvdebbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bread-line" /></template>
