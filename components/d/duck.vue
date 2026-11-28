<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryqrb3bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryqrb3bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:duck" /></template>
