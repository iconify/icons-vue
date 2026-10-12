<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2neunb3u.css';
import '../../css/h/h93-i1b7k.css';
import '../../css/d/d15udw7rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="h93-i1b7k"/><path class="d15udw7rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-circle-down-48-bold" /></template>
