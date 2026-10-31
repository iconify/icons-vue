<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-45c4bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-45c4bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:command-duocolor-round" /></template>
