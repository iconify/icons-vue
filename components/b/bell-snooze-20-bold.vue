<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6vbh3spu.css';
import '../../css/k/kwnn45cyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d6vbh3spu"/><path class="kwnn45cyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-snooze-20-bold" /></template>
