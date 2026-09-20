<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umgw0flwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umgw0flwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-history-fill" /></template>
