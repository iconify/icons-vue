<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9t00gb6u.css';
import '../../css/u/ujj6t-i1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9t00gb6u"/><path class="ujj6t-i1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-48" /></template>
