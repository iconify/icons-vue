<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqx115b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqx115b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gallery-vertical-line" /></template>
