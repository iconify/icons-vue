<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt6747b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yt6747b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:2-circle-fill" /></template>
