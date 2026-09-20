<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv7d94b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv7d94b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:category" /></template>
