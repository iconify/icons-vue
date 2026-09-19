<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2sacr10w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s2sacr10w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:digital-ocean" /></template>
