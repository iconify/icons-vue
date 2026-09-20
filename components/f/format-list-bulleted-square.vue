<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3h1mebjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3h1mebjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-list-bulleted-square" /></template>
