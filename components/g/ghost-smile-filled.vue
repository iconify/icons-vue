<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml1c0yf4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ml1c0yf4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ghost-smile-filled" /></template>
