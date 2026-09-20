<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rha8oacpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rha8oacpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-horizontal-start-sharp" /></template>
