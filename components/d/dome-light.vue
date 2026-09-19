<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovyu2kbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":48};
const content = `<path class="ovyu2kbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dome-light" /></template>
