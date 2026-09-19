<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwp8fo_vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vwp8fo_vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:gist-secret" /></template>
