<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nop3be92g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nop3be92g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:flotation-ring" /></template>
