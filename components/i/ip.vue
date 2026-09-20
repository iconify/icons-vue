<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkealni5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hkealni5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:ip" /></template>
