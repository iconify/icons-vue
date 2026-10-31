<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxty1nqgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxty1nqgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-close-round" /></template>
