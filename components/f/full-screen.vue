<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sye3enc-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sye3enc-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:full-screen" /></template>
