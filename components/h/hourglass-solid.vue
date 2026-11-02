<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up0ne41nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up0ne41nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:hourglass-solid" /></template>
