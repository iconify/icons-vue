<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvaovg4de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvaovg4de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hopr" /></template>
