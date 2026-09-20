<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyny2tbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qyny2tbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dalibo-light" /></template>
