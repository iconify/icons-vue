<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp8wsbcdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xp8wsbcdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-uturn-up-left" /></template>
