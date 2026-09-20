<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udtxlyb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="udtxlyb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-tablet" /></template>
