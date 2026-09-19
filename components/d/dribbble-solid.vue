<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw8n9btnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw8n9btnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:dribbble-solid" /></template>
