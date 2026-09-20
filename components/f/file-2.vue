<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6cu__b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p6cu__b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-2" /></template>
