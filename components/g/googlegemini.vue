<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmw28rbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmw28rbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlegemini" /></template>
