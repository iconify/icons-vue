<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhv2vsb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhv2vsb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-large-duocolor-round" /></template>
