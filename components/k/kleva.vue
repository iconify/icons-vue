<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwjj_mb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwjj_mb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kleva" /></template>
