<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2jgm9-lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="e2jgm9-lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cut-filled" /></template>
