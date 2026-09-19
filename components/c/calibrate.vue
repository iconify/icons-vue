<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ple5b9loz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ple5b9loz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:calibrate" /></template>
