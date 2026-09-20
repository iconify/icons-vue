<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmg4esbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmg4esbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward-right" /></template>
