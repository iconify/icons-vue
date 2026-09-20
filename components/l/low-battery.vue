<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5tonre-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q5tonre-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:low-battery" /></template>
