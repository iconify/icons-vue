<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyy2bibww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fyy2bibww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:direction-adjustment-three" /></template>
