<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnq21wbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wnq21wbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-text-right-solid" /></template>
