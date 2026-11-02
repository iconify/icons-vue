<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u28i3mbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u28i3mbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forbid-circle-fill" /></template>
