<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypv2wabxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ypv2wabxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:align-horizontal-center-two" /></template>
