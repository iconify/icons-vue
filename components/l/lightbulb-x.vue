<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw2yixbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw2yixbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:lightbulb-x" /></template>
