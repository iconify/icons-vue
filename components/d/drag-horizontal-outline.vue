<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-91d64oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r-91d64oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:drag-horizontal-outline" /></template>
