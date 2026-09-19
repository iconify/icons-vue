<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q56ww9qjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q56ww9qjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:diameter-solid" /></template>
