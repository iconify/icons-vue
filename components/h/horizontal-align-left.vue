<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe774vber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe774vber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:horizontal-align-left" /></template>
