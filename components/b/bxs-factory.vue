<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih55uac0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih55uac0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-factory" /></template>
