<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp9jrqb6k.css';
import '../../css/e/efx3s8brg.css';
import '../../css/k/kf8qud5kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hp9jrqb6k"/><path class="efx3s8brg"/><path class="kf8qud5kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-clock-20" /></template>
