<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dujg6qgto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dujg6qgto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-d20" /></template>
