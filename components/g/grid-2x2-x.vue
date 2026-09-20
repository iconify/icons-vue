<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q81ajacrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q81ajacrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:grid-2x2-x" /></template>
