<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd9e6acip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xd9e6acip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:clapperboard" /></template>
