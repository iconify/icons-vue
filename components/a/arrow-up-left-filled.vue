<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr5v-mbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr5v-mbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-left-filled" /></template>
