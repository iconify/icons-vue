<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul8ucqbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul8ucqbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-round" /></template>
