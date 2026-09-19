<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ursm7abnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ursm7abnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyboard-filled" /></template>
