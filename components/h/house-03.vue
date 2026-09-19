<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6kss8baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6kss8baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:house-03" /></template>
