<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il1_u-b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="il1_u-b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:entertainment-events-hobbies-horror-ghost" /></template>
