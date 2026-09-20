<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh3owmujd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hh3owmujd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:calendar-add" /></template>
