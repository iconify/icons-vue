<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dei3w-brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dei3w-brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-clock" /></template>
