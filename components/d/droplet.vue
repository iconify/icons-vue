<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmsq5rb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmsq5rb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:droplet" /></template>
