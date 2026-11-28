<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv1hcrjrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv1hcrjrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gauge-circle-solid" /></template>
