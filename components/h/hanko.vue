<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyop8zbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oyop8zbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hanko" /></template>
