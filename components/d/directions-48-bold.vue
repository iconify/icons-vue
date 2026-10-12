<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqnn4pbcu.css';
import '../../css/y/ykmr2x2jm.css';
import '../../css/c/cc2lz2byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iqnn4pbcu"/><path class="ykmr2x2jm"/><path class="cc2lz2byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:directions-48-bold" /></template>
