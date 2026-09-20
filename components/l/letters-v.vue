<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8wnmp3xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8wnmp3xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-v" /></template>
