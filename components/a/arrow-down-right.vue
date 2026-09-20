<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjic6qb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjic6qb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:arrow-down-right" /></template>
