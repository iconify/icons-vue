<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwoi47dhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwoi47dhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:badge" /></template>
