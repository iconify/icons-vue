<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e54cwys7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e54cwys7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:internet-archive-dark" /></template>
