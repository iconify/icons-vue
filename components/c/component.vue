<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipl4zsbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipl4zsbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:component" /></template>
