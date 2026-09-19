<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-g68ybph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-g68ybph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-tumblr" /></template>
