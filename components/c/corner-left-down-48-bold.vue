<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z87jsv16f.css';
import '../../css/g/gr2hwkk9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z87jsv16f"/><path class="gr2hwkk9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-left-down-48-bold" /></template>
