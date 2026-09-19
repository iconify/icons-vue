<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baes3_9xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="baes3_9xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:brass-eye" /></template>
