<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej_--k9hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej_--k9hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-more-line" /></template>
