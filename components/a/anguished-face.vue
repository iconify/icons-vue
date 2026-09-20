<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1849ip8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q1849ip8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:anguished-face" /></template>
