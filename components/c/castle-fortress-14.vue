<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kof4q9x0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kof4q9x0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:castle-fortress-14" /></template>
