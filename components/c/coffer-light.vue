<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrfln6yfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jrfln6yfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coffer-light" /></template>
