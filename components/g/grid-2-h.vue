<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl27z12fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl27z12fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:grid-2-h" /></template>
