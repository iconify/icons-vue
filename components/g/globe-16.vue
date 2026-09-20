<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plpghf1-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="plpghf1-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:globe-16" /></template>
