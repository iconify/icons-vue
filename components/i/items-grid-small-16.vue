<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8md-gbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q8md-gbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:items-grid-small-16" /></template>
