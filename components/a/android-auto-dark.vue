<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icu7kjy8b.css';
import '../../css/t/tncgtrlau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="icu7kjy8b"/><path class="tncgtrlau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:android-auto-dark" /></template>
