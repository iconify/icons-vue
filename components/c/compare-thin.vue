<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8-s3s_ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8-s3s_ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:compare-thin" /></template>
