<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v84ai0bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v84ai0bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lastdotfm" /></template>
