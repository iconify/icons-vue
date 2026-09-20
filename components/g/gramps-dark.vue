<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y73relbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y73relbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gramps-dark" /></template>
