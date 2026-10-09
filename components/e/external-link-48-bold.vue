<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkc0ul0xf.css';
import '../../css/j/jgs4mub3w.css';
import '../../css/l/led_7kbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jkc0ul0xf"/><path class="jgs4mub3w"/><path class="led_7kbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:external-link-48-bold" /></template>
