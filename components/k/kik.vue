<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ue90bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s2ue90bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:kik" /></template>
