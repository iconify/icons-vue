<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft31dgr8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft31dgr8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-undo-down-left" /></template>
