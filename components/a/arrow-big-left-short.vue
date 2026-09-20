<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd9vcdc9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd9vcdc9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-left-short" /></template>
