<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0mcxk10l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o0mcxk10l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docker" /></template>
