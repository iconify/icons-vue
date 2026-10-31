<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el40pyb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el40pyb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-plus-round" /></template>
