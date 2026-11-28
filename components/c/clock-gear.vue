<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-v3vibll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-v3vibll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clock-gear" /></template>
