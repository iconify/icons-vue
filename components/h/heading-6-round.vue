<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6iq38gjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6iq38gjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-6-round" /></template>
