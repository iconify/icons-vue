<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9885dbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9885dbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jupyter" /></template>
