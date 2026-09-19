<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqfdsvbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqfdsvbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:cloud-check" /></template>
