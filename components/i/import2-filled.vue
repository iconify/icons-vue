<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ingrhdrmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ingrhdrmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:import2-filled" /></template>
