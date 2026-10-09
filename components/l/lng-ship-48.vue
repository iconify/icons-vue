<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv3v9_bgq.css';
import '../../css/w/wegdy5b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kv3v9_bgq"/><path class="wegdy5b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lng-ship-48" /></template>
