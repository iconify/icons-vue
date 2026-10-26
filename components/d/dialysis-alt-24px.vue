<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs6magbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rs6magbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:dialysis-alt-24px" /></template>
