<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sob7tgzjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sob7tgzjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:axe-in-log" /></template>
