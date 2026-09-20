<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfb80zbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nfb80zbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:keyboard" /></template>
