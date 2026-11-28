<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea242b_ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea242b_ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bread-heart" /></template>
