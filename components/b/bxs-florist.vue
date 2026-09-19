<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv4c8bc2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv4c8bc2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-florist" /></template>
