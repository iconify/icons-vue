<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a92y3xrqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a92y3xrqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:id-card" /></template>
