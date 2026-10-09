<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpi6w4uli.css';
import '../../css/l/llqv7ablr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xpi6w4uli"/><path class="llqv7ablr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-conditioner-48" /></template>
