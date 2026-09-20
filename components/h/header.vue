<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk0-2pbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yk0-2pbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:header" /></template>
