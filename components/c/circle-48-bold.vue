<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2neunb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circle-48-bold" /></template>
