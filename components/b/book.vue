<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e65cizbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e65cizbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:book" /></template>
