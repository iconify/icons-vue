<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc9zikbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tc9zikbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:full-screen" /></template>
