<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz3ws0e7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vz3ws0e7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hi" /></template>
