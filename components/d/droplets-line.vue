<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya-2g1bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya-2g1bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:droplets-line" /></template>
