<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb8q_2bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qb8q_2bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:groly-dark" /></template>
