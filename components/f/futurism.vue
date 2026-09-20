<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3df32ggd.css';
import '../../css/r/rsbp7epmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3df32ggd"/><path class="rsbp7epmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:futurism" /></template>
