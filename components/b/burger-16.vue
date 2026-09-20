<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3ttebb7p.css';
import '../../css/k/km_nv7h3m.css';
import '../../css/l/lahok-bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e3ttebb7p"/><path class="km_nv7h3m"/><path class="lahok-bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:burger-16" /></template>
