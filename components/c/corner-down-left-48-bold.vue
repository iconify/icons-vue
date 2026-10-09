<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7kb9t1gf.css';
import '../../css/f/fj-2afnlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s7kb9t1gf"/><path class="fj-2afnlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-down-left-48-bold" /></template>
