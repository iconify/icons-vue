<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7f57udbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7f57udbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audiodeck-light" /></template>
