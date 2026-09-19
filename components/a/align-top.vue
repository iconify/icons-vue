<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evh9_l6tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evh9_l6tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:align-top" /></template>
