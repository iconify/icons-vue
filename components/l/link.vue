<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0er5_b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w0er5_b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:link" /></template>
