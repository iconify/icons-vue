<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7-8rccxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7-8rccxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-left-fill-round" /></template>
