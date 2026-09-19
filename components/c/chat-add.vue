<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aatk8ws5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aatk8ws5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-add" /></template>
