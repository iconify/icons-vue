<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir6w98bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ir6w98bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:add-four" /></template>
