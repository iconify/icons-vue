<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f46n3wgqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f46n3wgqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:l3x" /></template>
