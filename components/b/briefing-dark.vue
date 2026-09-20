<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipj5opk4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipj5opk4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:briefing-dark" /></template>
