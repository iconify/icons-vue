<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3dlznb6l.css';
import '../../css/f/f8640sn0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l3dlznb6l"/><path class="f8640sn0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frying-pan-48-bold" /></template>
