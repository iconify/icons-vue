<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvg0d3b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvg0d3b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:link-sharp-fill" /></template>
