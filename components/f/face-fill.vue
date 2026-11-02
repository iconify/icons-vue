<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isb1evb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isb1evb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:face-fill" /></template>
