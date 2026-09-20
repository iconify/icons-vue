<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oslnjoabo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oslnjoabo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keeper" /></template>
