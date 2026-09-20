<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md_2q2xyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="md_2q2xyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-reload-horizontal-1-flat" /></template>
