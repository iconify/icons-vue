<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0zvjwo1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m0zvjwo1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:airplane" /></template>
