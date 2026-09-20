<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwx53sbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwx53sbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:crown2-filled" /></template>
