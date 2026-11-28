<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4t8biyfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4t8biyfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:boxes-plus" /></template>
