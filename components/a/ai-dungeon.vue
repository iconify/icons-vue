<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oopk6j_9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oopk6j_9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ai-dungeon" /></template>
