<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsim1g_de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsim1g_de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-down-wide-narrow-fill" /></template>
