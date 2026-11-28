<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjfk6babz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfk6babz primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-duotone" /></template>
