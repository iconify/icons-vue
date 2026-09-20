<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydh90c3is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydh90c3is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fx-filled" /></template>
