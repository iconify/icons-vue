<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooub8eoja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooub8eoja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-down-left-linear" /></template>
