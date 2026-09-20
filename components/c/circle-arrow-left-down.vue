<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl1csjl3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vl1csjl3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-left-down" /></template>
