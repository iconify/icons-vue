<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cna79bboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cna79bboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:command-palette-24" /></template>
