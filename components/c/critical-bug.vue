<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9g4ubc9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9g4ubc9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:critical-bug" /></template>
