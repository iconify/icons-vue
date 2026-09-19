<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn6krnluk.css';
import '../../css/x/xlghf-tyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn6krnluk"/><path class="xlghf-tyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:discussion-filled" /></template>
