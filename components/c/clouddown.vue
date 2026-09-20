<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss_8yf0lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ss_8yf0lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:clouddown" /></template>
