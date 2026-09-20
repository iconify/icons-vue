<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl809_b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl809_b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gmail-cleaner" /></template>
