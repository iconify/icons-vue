<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxl5jackx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxl5jackx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2-fill" /></template>
