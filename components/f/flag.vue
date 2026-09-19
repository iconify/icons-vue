<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2ze5rb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2ze5rb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:flag" /></template>
