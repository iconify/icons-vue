<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oil6zn__w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oil6zn__w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apc-dark" /></template>
