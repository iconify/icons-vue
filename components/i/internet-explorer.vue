<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tob-p7yon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tob-p7yon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:internet-explorer" /></template>
