<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/css7eeb7b.css';
import '../../css/s/sfw5-4b4t.css';
import '../../css/l/l8okk4b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="css7eeb7b"/><path class="sfw5-4b4t"/><path class="l8okk4b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:greenhouse-48-bold" /></template>
