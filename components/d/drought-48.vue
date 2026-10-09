<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1acdg4aa.css';
import '../../css/i/ic7c7lbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r1acdg4aa"/><path class="ic7c7lbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drought-48" /></template>
