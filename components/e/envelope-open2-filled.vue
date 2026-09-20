<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtk1hdbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qtk1hdbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:envelope-open2-filled" /></template>
