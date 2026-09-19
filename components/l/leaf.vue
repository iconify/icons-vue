<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nerf759of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="nerf759of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:leaf" /></template>
