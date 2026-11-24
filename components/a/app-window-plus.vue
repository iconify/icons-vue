<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0yhc4j3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0yhc4j3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:app-window-plus" /></template>
