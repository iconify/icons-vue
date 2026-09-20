<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5rw2ua2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w5rw2ua2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:cinema-14" /></template>
