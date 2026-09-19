<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcqetdbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcqetdbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:grass" /></template>
