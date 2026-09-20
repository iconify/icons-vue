<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvw_5zbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uvw_5zbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:escalator-up" /></template>
