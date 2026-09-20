<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvuv9-98d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvuv9-98d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-pyramid" /></template>
