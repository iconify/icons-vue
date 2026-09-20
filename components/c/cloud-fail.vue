<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzfegx0sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tzfegx0sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-fail" /></template>
