<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbni4v0-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbni4v0-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-refresh" /></template>
