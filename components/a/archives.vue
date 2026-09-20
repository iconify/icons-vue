<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_enfybsp.css';
import '../../css/r/rrjee4b2a.css';
import '../../css/z/ztx3gnhsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z_enfybsp"/><path class="rrjee4b2a"/><path class="ztx3gnhsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:archives" /></template>
