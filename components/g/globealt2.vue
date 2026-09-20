<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntcdgkbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ntcdgkbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:globealt2" /></template>
