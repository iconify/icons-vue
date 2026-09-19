<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_spsnbot.css';
import '../../css/j/jgbcgmb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_spsnbot"/><path class="jgbcgmb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:accessibility" /></template>
