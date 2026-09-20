<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/splw5nbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="splw5nbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-3x3-outline" /></template>
