<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjglo8b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjglo8b6d primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-left-duotone" /></template>
