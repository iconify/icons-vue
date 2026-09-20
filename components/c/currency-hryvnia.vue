<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv2c5pl3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv2c5pl3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-hryvnia" /></template>
