<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlx70ub6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="nlx70ub6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:asterisk" /></template>
