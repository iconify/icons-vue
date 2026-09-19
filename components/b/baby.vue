<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfjn-7gcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfjn-7gcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:baby" /></template>
