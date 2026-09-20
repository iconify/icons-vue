<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blvs_rbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blvs_rbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:gaugechart" /></template>
