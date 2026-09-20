<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqqvpg69l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sqqvpg69l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:globealt" /></template>
