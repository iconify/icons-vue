<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9nqk8bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g9nqk8bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fog-48" /></template>
