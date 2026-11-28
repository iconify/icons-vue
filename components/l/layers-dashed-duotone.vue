<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxgfvg45l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxgfvg45l primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-dashed-duotone" /></template>
