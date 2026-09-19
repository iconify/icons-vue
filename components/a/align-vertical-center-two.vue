<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h58bwuevw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h58bwuevw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:align-vertical-center-two" /></template>
