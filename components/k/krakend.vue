<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3yb8ub5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j3yb8ub5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:krakend" /></template>
