<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1ku5-4fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e1ku5-4fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:hard-reset" /></template>
