<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bibqapb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bibqapb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laptop-48-bold" /></template>
