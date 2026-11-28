<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaz-w9bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaz-w9bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:infinity" /></template>
