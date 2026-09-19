<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdi4gp9eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdi4gp9eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-info-filled" /></template>
