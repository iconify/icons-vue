<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8pbcqbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8pbcqbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:basket-plus-outline" /></template>
