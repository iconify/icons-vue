<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvo4uuivi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jvo4uuivi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:horse-face" /></template>
