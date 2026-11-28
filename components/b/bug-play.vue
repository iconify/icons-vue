<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0n90cc4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0n90cc4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bug-play" /></template>
