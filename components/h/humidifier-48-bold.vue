<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlyw1hblf.css';
import '../../css/v/v4j2tfucd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlyw1hblf"/><path class="v4j2tfucd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:humidifier-48-bold" /></template>
