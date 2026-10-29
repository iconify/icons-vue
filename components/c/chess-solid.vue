<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9fb-ccxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9fb-ccxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chess-solid" /></template>
