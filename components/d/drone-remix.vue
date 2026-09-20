<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6c7vbb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v6c7vbb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:drone-remix" /></template>
