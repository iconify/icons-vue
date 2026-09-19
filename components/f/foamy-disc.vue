<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey91ksbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ey91ksbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:foamy-disc" /></template>
