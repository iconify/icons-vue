<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd3ym2bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd3ym2bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-6-circle-fill" /></template>
