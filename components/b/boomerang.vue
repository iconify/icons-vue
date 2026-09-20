<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivz70yb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ivz70yb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:boomerang" /></template>
