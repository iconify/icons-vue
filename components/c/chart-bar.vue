<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj7z6mb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj7z6mb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar" /></template>
