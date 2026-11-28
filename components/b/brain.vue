<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omryd1bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omryd1bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:brain" /></template>
