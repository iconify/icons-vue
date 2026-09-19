<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-p7vfblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="q-p7vfblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:calendar" /></template>
