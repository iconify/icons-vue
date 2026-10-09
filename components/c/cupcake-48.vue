<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_lg07b5j.css';
import '../../css/m/mq-hp4bft.css';
import '../../css/j/jw7uenmxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i_lg07b5j"/><path class="mq-hp4bft"/><path class="jw7uenmxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cupcake-48" /></template>
