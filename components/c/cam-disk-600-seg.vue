<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsw5o6x4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsw5o6x4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cam-disk-600-seg" /></template>
