<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgl5pmbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgl5pmbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:export2-filled" /></template>
