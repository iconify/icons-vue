<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvx6gqv2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvx6gqv2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flatnotes-dark" /></template>
