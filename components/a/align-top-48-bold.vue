<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cntw57bva.css';
import '../../css/q/q4ayogbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cntw57bva"/><path class="q4ayogbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-top-48-bold" /></template>
