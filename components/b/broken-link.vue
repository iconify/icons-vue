<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hphbwmrgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":496};
const content = `<path class="hphbwmrgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:broken-link" /></template>
