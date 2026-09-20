<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbj0pbvta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbj0pbvta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clubs-fill" /></template>
