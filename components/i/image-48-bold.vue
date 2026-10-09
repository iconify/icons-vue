<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcfuqov3g.css';
import '../../css/m/mdy5cy31n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gcfuqov3g"/><path class="mdy5cy31n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-48-bold" /></template>
