<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaihz8b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaihz8b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-vertically-filled" /></template>
