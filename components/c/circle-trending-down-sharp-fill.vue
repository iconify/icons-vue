<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhra1rbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhra1rbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-trending-down-sharp-fill" /></template>
