<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb7e86lle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xb7e86lle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:emoji-happy" /></template>
