<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhmi6qb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhmi6qb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:drawing-compass-filled" /></template>
