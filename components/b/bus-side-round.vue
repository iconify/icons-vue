<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnbua4b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnbua4b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-side-round" /></template>
