<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj9keacby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sj9keacby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:archive-register" /></template>
