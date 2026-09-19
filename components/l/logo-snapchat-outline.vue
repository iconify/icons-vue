<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klmaeib4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klmaeib4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-snapchat-outline" /></template>
