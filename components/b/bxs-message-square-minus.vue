<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh2t47oxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh2t47oxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-square-minus" /></template>
