<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrmpk-mlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrmpk-mlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-wifi2-filled" /></template>
