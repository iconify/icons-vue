<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgpnn41og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgpnn41og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:briefcases-line" /></template>
