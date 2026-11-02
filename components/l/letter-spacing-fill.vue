<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cilo2uhhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cilo2uhhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:letter-spacing-fill" /></template>
