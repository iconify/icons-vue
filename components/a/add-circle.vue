<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyk7swgfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyk7swgfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:add-circle" /></template>
