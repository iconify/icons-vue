<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb70uhhrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<path class="tb70uhhrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bottom-bar-one" /></template>
