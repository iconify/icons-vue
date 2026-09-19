<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nilgi0bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nilgi0bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:between-horizontal-start" /></template>
