<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ireq_876v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ireq_876v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:diagonal-scroll-1" /></template>
