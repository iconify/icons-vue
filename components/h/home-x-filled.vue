<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn2qdwnff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wn2qdwnff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-x-filled" /></template>
