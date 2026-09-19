<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i18_uccwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i18_uccwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-turn-up" /></template>
