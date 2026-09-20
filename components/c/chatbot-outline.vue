<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw069obaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nw069obaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:chatbot-outline" /></template>
