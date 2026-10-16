<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tht13fb0t.css';
import '../../css/d/d9xo1bc7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tht13fb0t"/><path class="d9xo1bc7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chainsaw-48" /></template>
