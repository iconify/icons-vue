<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f26qfobhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f26qfobhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:calendar" /></template>
