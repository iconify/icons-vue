<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oet0gjbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oet0gjbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:fire" /></template>
