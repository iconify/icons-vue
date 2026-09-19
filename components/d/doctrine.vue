<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u641ht8nk.css';
import '../../css/e/efxthlbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u641ht8nk"/><path class="efxthlbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:doctrine" /></template>
