<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz3wsbcfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pz3wsbcfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:circle" /></template>
