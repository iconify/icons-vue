<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijs8fxbia.css';
import '../../css/w/w8537imoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ijs8fxbia"/><path class="w8537imoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aquifer-20" /></template>
