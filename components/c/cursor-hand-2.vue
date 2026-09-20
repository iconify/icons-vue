<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1-c8qbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1-c8qbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cursor-hand-2" /></template>
