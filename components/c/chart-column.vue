<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nit84jbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nit84jbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-column" /></template>
