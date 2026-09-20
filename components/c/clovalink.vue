<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1xnr0bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a1xnr0bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clovalink" /></template>
