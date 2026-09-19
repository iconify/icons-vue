<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9hn6abln.css';
import '../../css/n/nsui017pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p9hn6abln"/><path class="nsui017pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:group-security" /></template>
