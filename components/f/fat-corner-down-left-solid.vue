<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prquawbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prquawbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-down-left-solid" /></template>
