<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6a66hhkg.css';
import '../../css/h/h2yezpf2d.css';
import '../../css/e/ev4sdmbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q6a66hhkg"/><path class="h2yezpf2d"/><path class="ev4sdmbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-balancing-48" /></template>
