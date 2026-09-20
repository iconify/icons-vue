<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkp4jebtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xkp4jebtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-favorite-heart-remix" /></template>
