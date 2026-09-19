<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce32om2az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce32om2az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:filter-mail-remove" /></template>
