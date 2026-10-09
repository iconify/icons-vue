<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex6kn_g6k.css';
import '../../css/s/s1dmhkb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ex6kn_g6k"/><path class="s1dmhkb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chef-knife-48" /></template>
