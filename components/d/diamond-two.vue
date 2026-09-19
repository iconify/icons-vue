<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqn04vbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eqn04vbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:diamond-two" /></template>
