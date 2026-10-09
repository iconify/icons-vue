<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0j8550vr.css';
import '../../css/b/bxkvxsbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s0j8550vr"/><path clip-rule="evenodd" class="bxkvxsbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-ground-48" /></template>
