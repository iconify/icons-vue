<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/honyfv0bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="honyfv0bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:basic-memory-light" /></template>
