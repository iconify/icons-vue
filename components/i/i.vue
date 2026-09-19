<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phux6hbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":82,"height":690};
const content = `<path class="phux6hbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:i" /></template>
