<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rifz72xdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rifz72xdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alby-hub" /></template>
