<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwuy1sbez.css';
import '../../css/f/ff9jhsbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dwuy1sbez"/><rect class="ff9jhsbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:lock-open-outline" /></template>
