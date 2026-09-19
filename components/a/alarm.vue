<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee9pe2b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee9pe2b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:alarm" /></template>
