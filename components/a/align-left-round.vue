<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whde9goyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whde9goyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-left-round" /></template>
