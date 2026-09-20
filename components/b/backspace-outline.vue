<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxx9vvbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxx9vvbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:backspace-outline" /></template>
